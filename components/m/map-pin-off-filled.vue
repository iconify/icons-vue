<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da33ryhuh.css';
import '../../css/g/gnqvxofvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="da33ryhuh"/><path class="gnqvxofvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:map-pin-off-filled" /></template>
