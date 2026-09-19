<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/g/gbh1v2c4l.css';
import '../../css/t/ts-hhubnq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGwfzB1hJq"><g class="v3_i3wktz"><path class="gbh1v2c4l"/><path class="ts-hhubnq"/></g></mask></defs><path mask="url(#SVGwfzB1hJq)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:stopwatch-start" /></template>
