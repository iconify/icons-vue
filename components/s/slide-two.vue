<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/f/fzt9c0b2m.css';
import '../../css/m/md9y_u8eo.css';
import '../../css/x/xp4tznbvo.css';
import '../../css/y/y3_vjac4a.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGuwVzTZxk"><g class="wwvp95byt"><path class="fzt9c0b2m"/><path clip-rule="evenodd" class="md9y_u8eo"/><path class="xp4tznbvo"/><path class="y3_vjac4a"/></g></mask></defs><path mask="url(#SVGuwVzTZxk)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:slide-two" /></template>
