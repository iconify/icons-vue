<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otc4z1bni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otc4z1bni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:pendantround" /></template>
