<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s09_o6rsp.css';
import '../../css/a/a0j8fkmhb.css';
import '../../css/l/ln35q8plx.css';
import '../../css/g/g7dhhz-fw.css';
import '../../css/n/nvr01tbel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s09_o6rsp"/><path class="a0j8fkmhb"/><path class="ln35q8plx"/><path class="g7dhhz-fw"/><path class="nvr01tbel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:palette-2-bold-duotone" /></template>
