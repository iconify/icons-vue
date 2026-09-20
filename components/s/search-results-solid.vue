<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq9z85bal.css';
import '../../css/x/xlo2ptjbm.css';
import '../../css/k/kemfy5bie.css';
import '../../css/e/eu-9hmdib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zq9z85bal"/><path class="xlo2ptjbm"/><path clip-rule="evenodd" class="kemfy5bie"/><path class="eu-9hmdib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:search-results-solid" /></template>
