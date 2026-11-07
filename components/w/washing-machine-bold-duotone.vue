<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cixwhxber.css';
import '../../css/a/awwld0a_d.css';
import '../../css/o/o1a-n2i9j.css';
import '../../css/s/sg0-5cb7e.css';
import '../../css/x/xgyldlbls.css';
import '../../css/v/vrxvbepbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cixwhxber"/><path clip-rule="evenodd" class="awwld0a_d"/><path class="o1a-n2i9j"/><path class="sg0-5cb7e"/><path class="xgyldlbls"/><path class="vrxvbepbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:washing-machine-bold-duotone" /></template>
