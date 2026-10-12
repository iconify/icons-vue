<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzhh08_zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pzhh08_zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:message-square-heart-filled" /></template>
