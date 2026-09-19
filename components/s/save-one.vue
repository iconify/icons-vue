<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/f/f_85gibla.css';
import '../../css/e/e3j8mebgs.css';
import '../../css/n/n2grqgz0s.css';
import '../../css/t/t0oyecvos.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGthzZLJZS"><g class="s9cl3zbei"><path class="f_85gibla"/><path class="e3j8mebgs"/><path class="n2grqgz0s"/><path class="t0oyecvos"/></g></mask></defs><path mask="url(#SVGthzZLJZS)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:save-one" /></template>
