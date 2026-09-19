<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/c/crnb93ntl.css';
import '../../css/c/c575j-byr.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGKkdZ2csA"><g class="wwvp95byt"><path class="crnb93ntl"/><path class="c575j-byr"/></g></mask></defs><path mask="url(#SVGKkdZ2csA)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:success" /></template>
