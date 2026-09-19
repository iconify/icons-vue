<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brj8jwbvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brj8jwbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:navigation-2" /></template>
