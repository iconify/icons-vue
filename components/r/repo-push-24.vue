<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3aizm_py.css';
import '../../css/q/qeheuacbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3aizm_py"/><path class="qeheuacbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:repo-push-24" /></template>
