<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zovel4bbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zovel4bbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:uni8279-circled-filled" /></template>
