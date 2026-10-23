<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm82hpbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pm82hpbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:regex" /></template>
