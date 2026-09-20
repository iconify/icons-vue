<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwo46jzka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwo46jzka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:opencode" /></template>
