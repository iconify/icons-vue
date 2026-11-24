<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y91zfqtmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y91zfqtmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:telescope-filled" /></template>
