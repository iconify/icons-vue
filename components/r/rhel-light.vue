<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp-vsxb4f.css';
import '../../css/w/ws9x54gvl.css';
import '../../css/v/vm_hfeb5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bp-vsxb4f"/><path class="ws9x54gvl"/><path class="vm_hfeb5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rhel-light" /></template>
