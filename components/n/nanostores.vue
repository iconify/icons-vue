<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq7zz_bpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nq7zz_bpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:nanostores" /></template>
