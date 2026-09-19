<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js3jstb1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="js3jstb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:signature" /></template>
