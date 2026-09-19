<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfqdl_ydw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfqdl_ydw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shopping-basket-check-out-03" /></template>
