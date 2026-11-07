<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be24kjn_m.css';
import '../../css/e/erff_3del.css';
import '../../css/y/yrcey2bdn.css';
import '../../css/b/biqv3ubbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="be24kjn_m"/><path class="erff_3del"/><path class="yrcey2bdn"/><path clip-rule="evenodd" class="biqv3ubbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:remote-controller-minimalistic-bold-duotone" /></template>
