<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/caw1b0bno.css';
import '../../css/f/fiugtjbdq.css';
import '../../css/h/hvf_gzblv.css';
import '../../css/h/hc3npei1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="caw1b0bno"/><path class="fiugtjbdq"/><path class="hvf_gzblv"/><path clip-rule="evenodd" class="hc3npei1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:password-outline" /></template>
