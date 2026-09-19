<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9n9aw2xv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c9n9aw2xv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-3-fill" /></template>
