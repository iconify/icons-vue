<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qywweimyl.css';
import '../../css/p/p-h1svb7w.css';
import '../../css/k/kkftzqzny.css';
import '../../css/l/lijdjv4wn.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGQEbOccRQ"><g class="ft5dv1b6b"><path class="qywweimyl"/><path class="p-h1svb7w"/><path class="kkftzqzny"/><path class="lijdjv4wn"/></g></mask></defs><path mask="url(#SVGQEbOccRQ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:play-basketball" /></template>
