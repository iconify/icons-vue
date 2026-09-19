<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvc_3lbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvc_3lbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:temple" /></template>
