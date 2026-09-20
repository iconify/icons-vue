<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnc0f53hn.css';
import '../../css/f/frfm2sm4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rnc0f53hn"/><path class="frfm2sm4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:upload-fill" /></template>
