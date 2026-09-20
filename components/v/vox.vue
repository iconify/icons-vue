<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4ep6p37u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4ep6p37u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:vox" /></template>
