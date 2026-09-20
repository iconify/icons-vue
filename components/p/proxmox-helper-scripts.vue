<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzec-gbac.css';
import '../../css/f/ff2dlhbix.css';
import '../../css/a/a7--3wfxj.css';
import '../../css/a/at489ww4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kzec-gbac"/><path class="ff2dlhbix"/><path class="a7--3wfxj"/><path class="at489ww4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proxmox-helper-scripts" /></template>
