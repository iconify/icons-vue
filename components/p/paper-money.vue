<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/c/cyzti895k.css';
import '../../css/c/cmbowxb1u.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGoxqT4cMo"><g class="ufeehvblu"><path class="cyzti895k"/><path class="cmbowxb1u"/></g></mask></defs><path mask="url(#SVGoxqT4cMo)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:paper-money" /></template>
