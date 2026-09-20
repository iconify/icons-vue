<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/momvlfb7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="momvlfb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:x-24" /></template>
