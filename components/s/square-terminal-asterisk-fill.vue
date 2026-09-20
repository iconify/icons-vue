<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkctlbcpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkctlbcpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-terminal-asterisk-fill" /></template>
