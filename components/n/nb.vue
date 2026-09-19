<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/u/u7oepjbfn.css';
import '../../css/k/k4nns9bme.css';
import '../../css/c/crjv6y_du.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="circleFlagsNb0"><circle class="bc1fd0lxe"/></mask><g mask="url(#circleFlagsNb0)"><path class="u7oepjbfn"/><path class="k4nns9bme"/><path class="crjv6y_du"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:nb" /></template>
