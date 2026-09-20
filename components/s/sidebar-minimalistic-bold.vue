<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrci20dmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rrci20dmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sidebar-minimalistic-bold" /></template>
