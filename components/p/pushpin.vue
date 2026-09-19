<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j848glbsj.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGXXXG9bEB"><path class="j848glbsj"/></mask></defs><path mask="url(#SVGXXXG9bEB)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:pushpin" /></template>
