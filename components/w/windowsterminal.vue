<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bou7yz9xf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bou7yz9xf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:windowsterminal" /></template>
