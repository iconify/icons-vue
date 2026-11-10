<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp_zz6bvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pp_zz6bvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:moped-filled" /></template>
