<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn1n_mb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sn1n_mb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:margin-right" /></template>
