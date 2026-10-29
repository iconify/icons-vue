<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iis1bcc9c.css';
import '../../css/j/jyoh2bcls.css';
import '../../css/l/lb7evabyl.css';
import '../../css/g/gppyxfbsu.css';
import '../../css/j/jpnldbbsr.css';
import '../../css/k/kg8_k7jys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iis1bcc9c wm-shadow"/><path class="jyoh2bcls wm-k"/><path class="lb7evabyl wm-k"/><path class="gppyxfbsu wm-k"/><path class="jpnldbbsr wm-k"/><path class="kg8_k7jys wm-shine"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:plus" /></template>
