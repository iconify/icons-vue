<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gctxmzx0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gctxmzx0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:picasa-logo-solid" /></template>
