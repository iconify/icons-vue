<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgy6n9bxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgy6n9bxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:phone-ringing-1" /></template>
