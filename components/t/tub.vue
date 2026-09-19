<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/k/k2-5ysdjd.css';
import '../../css/a/a79n19b8w.css';
import '../../css/k/k9kqlacbd.css';
import '../../css/y/yml010bne.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGJvSoycSG"><g class="hv130ab-t"><path class="k2-5ysdjd"/><path class="a79n19b8w"/><path class="k9kqlacbd"/><path class="yml010bne"/></g></mask></defs><path mask="url(#SVGJvSoycSG)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:tub" /></template>
