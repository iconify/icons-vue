<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyk415qex.css';
import '../../css/s/sokimzycn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyk415qex"/><path class="sokimzycn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:watermelon-filled" /></template>
