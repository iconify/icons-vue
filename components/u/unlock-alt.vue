<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3qd3j95h.css';
import '../../css/r/rixxe_b4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3qd3j95h"/><path class="rixxe_b4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:unlock-alt" /></template>
