<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6eo0_b0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6eo0_b0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:paperclip" /></template>
