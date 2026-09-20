<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz32jjbma.css';
import '../../css/m/mg-i62fru.css';
import '../../css/r/rzyax-b9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bz32jjbma"/><path class="mg-i62fru"/><path class="rzyax-b9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:web-section" /></template>
