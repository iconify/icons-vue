<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9vxvpbhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p9vxvpbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:video-file-fill" /></template>
