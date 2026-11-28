<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3sshkb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3sshkb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-moon-solid" /></template>
