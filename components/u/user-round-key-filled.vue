<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi8i8d0dt.css';
import '../../css/m/mgrdfsbgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pi8i8d0dt"/><path clip-rule="evenodd" class="mgrdfsbgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-round-key-filled" /></template>
