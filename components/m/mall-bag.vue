<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/e/ez7docclp.css';
import '../../css/f/fxrnyjbgc.css';
import '../../css/x/xzlilxrec.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGb4mctTCP"><g class="ufeehvblu"><path class="ez7docclp"/><path class="fxrnyjbgc"/><path class="xzlilxrec"/></g></mask></defs><path mask="url(#SVGb4mctTCP)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:mall-bag" /></template>
