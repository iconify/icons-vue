<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co2cki_7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="co2cki_7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:person-badge-minus-fill" /></template>
