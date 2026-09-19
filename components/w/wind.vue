<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bslj-5bzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bslj-5bzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:wind" /></template>
