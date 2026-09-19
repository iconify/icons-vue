<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1yuyjz7c.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG8oel7IvX"><path class="z1yuyjz7c"/></mask></defs><path mask="url(#SVG8oel7IvX)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:vertical-tidy-up" /></template>
