<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/d/dn_y4s9cj.css';
import '../../css/l/ly3952sva.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGxi7i2kST"><g class="ufeehvblu"><path class="dn_y4s9cj"/><path class="ly3952sva"/></g></mask></defs><path mask="url(#SVGxi7i2kST)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:switch-button" /></template>
