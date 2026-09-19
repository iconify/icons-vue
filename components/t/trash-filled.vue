<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwh7i9_ct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwh7i9_ct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:trash-filled" /></template>
