<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx1kr0e0u.css';
import '../../css/o/om7lkbccu.css';
import '../../css/k/kw8vl3bjo.css';
import '../../css/s/smbj7_bwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx1kr0e0u"/><path class="om7lkbccu"/><path class="kw8vl3bjo"/><path class="smbj7_bwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-speak-rounded-bold" /></template>
