<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dciv8jbgc.css';
import '../../css/h/hm0exmb8r.css';
import '../../css/p/pofhjrbui.css';
import '../../css/t/tmouilbdm.css';
import '../../css/w/w5d-t9y6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dciv8jbgc"/><path class="hm0exmb8r"/><path class="pofhjrbui"/><path class="tmouilbdm"/><path class="w5d-t9y6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:radio-bold-duotone" /></template>
