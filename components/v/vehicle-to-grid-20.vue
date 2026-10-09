<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr7_wabhq.css';
import '../../css/r/r3nawdb_c.css';
import '../../css/v/vhcr-o0os.css';
import '../../css/p/p1eda_bcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tr7_wabhq"/><path class="r3nawdb_c"/><path class="vhcr-o0os"/><path class="p1eda_bcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:vehicle-to-grid-20" /></template>
