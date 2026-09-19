<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/y/ygz7ebcej.css';
import '../../css/z/zx_6j6b3b.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGtszk6bSu"><g class="v3_i3wktz"><path class="ygz7ebcej"/><path class="zx_6j6b3b"/></g></mask></defs><path mask="url(#SVGtszk6bSu)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:voicemail" /></template>
