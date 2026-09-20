<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7lp3gbpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a7lp3gbpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:settings-cog-plus" /></template>
