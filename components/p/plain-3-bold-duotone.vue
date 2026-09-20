<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecxmxhl9m.css';
import '../../css/u/uhv43pf8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ecxmxhl9m"/><path class="uhv43pf8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:plain-3-bold-duotone" /></template>
