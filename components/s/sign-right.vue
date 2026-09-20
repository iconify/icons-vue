<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow2q_cqck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ow2q_cqck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:sign-right" /></template>
