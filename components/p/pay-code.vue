<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/w/wkaq4nb8y.css';
import '../../css/c/chwdkhbaz.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGxIXYQbJu"><g class="ufeehvblu"><path class="wkaq4nb8y"/><path class="chwdkhbaz"/></g></mask></defs><path mask="url(#SVGxIXYQbJu)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:pay-code" /></template>
