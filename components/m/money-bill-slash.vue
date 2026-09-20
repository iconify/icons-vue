<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9yiddczm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9yiddczm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:money-bill-slash" /></template>
