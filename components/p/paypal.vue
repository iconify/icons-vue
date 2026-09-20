<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn0c3r6yz.css';
import '../../css/z/zbdow5bzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tn0c3r6yz"/><path class="zbdow5bzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:paypal" /></template>
