<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx6sh1ufv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary qx6sh1ufv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:variable-duotone" /></template>
