<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmqoqs75f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-edit" /></template>
<style>
.cmqoqs75f {
  fill: currentColor;
  d: path("M14.23 20v-2.21l5.334-5.307q.148-.13.307-.19q.16-.062.32-.062q.165 0 .334.064q.17.065.298.194l.925.944q.123.148.187.308q.065.159.065.319t-.052.322t-.2.31L16.44 20zM5 18.616v-1.647q0-.619.36-1.158q.361-.54.97-.838q1.416-.679 2.834-1.018q1.417-.34 2.836-.34q.675 0 1.354.084t1.367.238l-2.875 2.855v1.824zm15.19-3.6l.925-.956l-.924-.944l-.95.95zM9.878 10.508Q9 9.63 9 8.385t.877-2.123T12 5.385t2.123.877T15 8.385t-.877 2.123t-2.123.877t-2.123-.877");
}

</style>
