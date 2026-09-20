<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rop6in0iw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rop6in0iw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:user-alt-3-fill" /></template>
