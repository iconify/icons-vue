<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na6boxbpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="na6boxbpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:perspective" /></template>
