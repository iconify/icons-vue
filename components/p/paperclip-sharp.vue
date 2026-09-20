<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_vehl7vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_vehl7vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:paperclip-sharp" /></template>
