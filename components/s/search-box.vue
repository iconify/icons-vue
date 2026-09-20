<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpe_zkb5e.css';
import '../../css/h/heok19bbn.css';
import '../../css/c/cz1u-qu3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpe_zkb5e"/><path class="heok19bbn"/><path class="cz1u-qu3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:search-box" /></template>
