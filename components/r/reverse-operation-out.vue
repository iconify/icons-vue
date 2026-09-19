<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/c/cej2n11nh.css';
import '../../css/g/g03ocyb3a.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGaRRqpcCp"><g class="wwvp95byt"><path class="cej2n11nh"/><path class="g03ocyb3a"/></g></mask></defs><path mask="url(#SVGaRRqpcCp)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:reverse-operation-out" /></template>
