<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btubcb-wd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="btubcb-wd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:thumbs-up-filled" /></template>
