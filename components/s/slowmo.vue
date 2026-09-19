<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag96a_b5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ag96a_b5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:slowmo" /></template>
