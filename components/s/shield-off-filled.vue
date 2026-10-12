<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcnrz_gkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcnrz_gkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shield-off-filled" /></template>
