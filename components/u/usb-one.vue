<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/s/sjfe-0i3c.css';
import '../../css/b/bj3s_utsy.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGqkY9ed0V"><g class="v3_i3wktz"><path class="sjfe-0i3c"/><path class="bj3s_utsy"/></g></mask></defs><path mask="url(#SVGqkY9ed0V)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:usb-one" /></template>
