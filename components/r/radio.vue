<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/t/toz1dpcji.css';
import '../../css/y/ysw8cmbcj.css';
import '../../css/w/w2xpt4b5w.css';
import '../../css/k/k-2sy8b0k.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGJrUFRl7h"><g class="s9cl3zbei"><rect class="toz1dpcji"/><circle class="ysw8cmbcj"/><path class="w2xpt4b5w"/><path class="k-2sy8b0k"/></g></mask></defs><path mask="url(#SVGJrUFRl7h)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:radio" /></template>
