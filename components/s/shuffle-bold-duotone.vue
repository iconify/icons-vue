<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv_hji6de.css';
import '../../css/s/s41nwo9jh.css';
import '../../css/k/k8ef9sbjl.css';
import '../../css/b/blczsbbja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv_hji6de"/><path class="s41nwo9jh"/><path class="k8ef9sbjl"/><path class="blczsbbja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shuffle-bold-duotone" /></template>
