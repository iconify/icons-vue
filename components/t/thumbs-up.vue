<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5qiuibuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k5qiuibuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:thumbs-up" /></template>
