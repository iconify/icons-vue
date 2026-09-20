<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcxe_dbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcxe_dbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:protonvpn" /></template>
