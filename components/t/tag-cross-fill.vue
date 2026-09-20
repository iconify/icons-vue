<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b75m-u-9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b75m-u-9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:tag-cross-fill" /></template>
