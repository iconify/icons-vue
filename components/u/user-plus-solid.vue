<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj3a1wbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lj3a1wbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:user-plus-solid" /></template>
