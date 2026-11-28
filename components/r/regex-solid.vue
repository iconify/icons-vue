<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h555ks16l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h555ks16l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:regex-solid" /></template>
