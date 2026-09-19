<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnm4t1t0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gnm4t1t0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:mobile-phone-solid" /></template>
