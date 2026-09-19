<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/w/w55in7b1i.css';
import '../../css/k/kj2o0vx9c.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGkRLQpbND"><g class="wwvp95byt"><path class="w55in7b1i"/><path class="kj2o0vx9c"/></g></mask></defs><path mask="url(#SVGkRLQpbND)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:weixin-mini-app" /></template>
