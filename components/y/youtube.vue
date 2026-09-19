<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3jh1-bnt.css';
import '../../css/d/dblasrb2v.css';
import '../../css/w/wxc7mbbhr.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGTk2kDbTG"><g class="q3jh1-bnt"><path class="dblasrb2v"/><path class="wxc7mbbhr"/></g></mask></defs><path mask="url(#SVGTk2kDbTG)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:youtube" /></template>
