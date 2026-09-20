<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn4zp1bkf.css';
import '../../css/a/anndn7kya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gn4zp1bkf"/><path class="anndn7kya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:qr-code-fill" /></template>
