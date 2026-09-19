<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp_4tvblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp_4tvblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:user-plus-filled" /></template>
