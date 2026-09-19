<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl4bzbcjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="pl4bzbcjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:uni5f97-box-filled" /></template>
