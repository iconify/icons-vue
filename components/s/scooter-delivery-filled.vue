<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjgduub1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjgduub1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:scooter-delivery-filled" /></template>
