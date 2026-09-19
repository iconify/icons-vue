<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/d/dnwl0o7kh.css';
import '../../css/t/t3p6ajbsy.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGjy7d7bhu"><g class="v3_i3wktz"><path class="dnwl0o7kh"/><path class="t3p6ajbsy"/></g></mask></defs><path mask="url(#SVGjy7d7bhu)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:usb" /></template>
