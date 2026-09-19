<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/reb798bgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="reb798bgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:meh-blank-filled" /></template>
