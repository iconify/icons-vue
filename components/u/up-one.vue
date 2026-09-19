<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf493jmyr.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGOquiGdSs"><path class="cf493jmyr"/></mask></defs><path mask="url(#SVGOquiGdSs)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:up-one" /></template>
