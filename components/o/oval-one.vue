<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz1736cer.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG68bY5cqX"><ellipse class="wz1736cer"/></mask></defs><path mask="url(#SVG68bY5cqX)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:oval-one" /></template>
