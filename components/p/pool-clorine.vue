<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm7w5bbqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gm7w5bbqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:pool-clorine" /></template>
