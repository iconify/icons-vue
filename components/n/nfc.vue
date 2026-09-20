<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9-gnsb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9-gnsb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:nfc" /></template>
