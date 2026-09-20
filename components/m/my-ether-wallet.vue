<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xujzs6iss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xujzs6iss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:my-ether-wallet" /></template>
