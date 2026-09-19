<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m14r7jbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="m14r7jbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:snow" /></template>
