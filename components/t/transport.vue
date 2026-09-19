<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/k/k87xdfbfj.css';
import '../../css/v/v8g1xozen.css';
import '../../css/w/w4vhh3s5s.css';
import '../../css/e/etmqncjox.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGcWmdtcgB"><g class="s9cl3zbei"><rect class="k87xdfbfj"/><path class="v8g1xozen"/><path class="w4vhh3s5s"/><path class="etmqncjox"/></g></mask></defs><path mask="url(#SVGcWmdtcgB)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:transport" /></template>
