<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfn3o34-i.css';
import '../../css/e/ecf1c0bzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfn3o34-i"/><path class="ecf1c0bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:repositories" /></template>
