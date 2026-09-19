<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf9lx2b7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mf9lx2b7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:user-cancel-filled" /></template>
