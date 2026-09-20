<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w76g3kfom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w76g3kfom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:phone-cancel" /></template>
