<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/i/i-ue65unp.css';
import '../../css/x/xj8egpbob.css';
import '../../css/o/o8dffdffr.css';
import '../../css/r/rl52ozmsz.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGk41ZVbSv"><g class="ufeehvblu"><path class="i-ue65unp"/><path class="xj8egpbob"/><path class="o8dffdffr"/><path class="rl52ozmsz"/></g></mask></defs><path mask="url(#SVGk41ZVbSv)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:skull" /></template>
