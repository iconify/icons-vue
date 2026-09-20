<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_936xi-v.css';
import '../../css/c/caqza3bpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_936xi-v"/><path class="caqza3bpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:search-results-light" /></template>
