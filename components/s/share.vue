<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n672586bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n672586bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:share" /></template>
