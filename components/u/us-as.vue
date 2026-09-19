<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/n/n4q3579np.css';
import '../../css/c/c2d8dlb9m.css';
import '../../css/p/p8rswpbhk.css';
import '../../css/n/n0kma69zb.css';
import '../../css/i/i8dwev7ug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGuywqVbel"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGuywqVbel)"><path class="n4q3579np"/><path class="c2d8dlb9m"/><path class="p8rswpbhk"/><path class="n0kma69zb"/><path class="i8dwev7ug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:us-as" /></template>
