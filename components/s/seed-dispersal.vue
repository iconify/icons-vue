<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnw2fh7yd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:seed-dispersal" /></template>
<style>
.mnw2fh7yd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.488 5.431Q12-.987 4.513 5.43l-.001.001q-.094.08-.157.187l-.006.01q-.058.101-.082.214q-.025.113-.014.229q.011.115.057.222q.045.107.121.195q.08.094.187.157l.01.006l6.622 3.784v4.415q-1.75.513-1.75 3.65q0 3.75 2.5 3.75q1.156 0 1.885-1.251q.615-1.054.615-2.499t-.615-2.499q-.476-.817-1.135-1.101v-4.465l6.622-3.784l.01-.006q.107-.063.187-.157q.11-.128.155-.291q.034-.125.024-.255q-.013-.168-.097-.314q-.064-.113-.163-.197m-1.817.464L12.75 8.708V3.816q2.461.243 4.921 2.079M11.25 8.708L6.329 5.895q2.46-1.836 4.921-2.079z");
}

</style>
