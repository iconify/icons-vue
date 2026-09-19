<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bba6mtbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bba6mtbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:usps" /></template>
