<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi0bh4bum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xi0bh4bum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:rainbow-solid" /></template>
