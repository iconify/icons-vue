<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tec5ddc1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tec5ddc1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:sign-out-duotone" /></template>
