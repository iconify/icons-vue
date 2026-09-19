<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahxe6_p3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ahxe6_p3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:text-bubble-fill" /></template>
