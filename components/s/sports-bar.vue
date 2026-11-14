<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwj6jtbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sports-bar" /></template>
<style>
.jwj6jtbco {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 6.25h-4.347l2.411-2.756q.099-.112.146-.254q.048-.141.038-.29t-.076-.282t-.178-.232t-.254-.146q-.141-.048-.29-.038t-.282.076t-.232.178L12 5.861L9.064 2.506q-.098-.112-.232-.178q-.133-.066-.282-.076t-.29.038q-.142.047-.254.146q-.055.048-.101.107q-.045.058-.077.125q-.033.066-.052.137t-.024.145t.004.147t.034.143q.023.07.06.134t.086.12l2.411 2.756H6q-1.76 0-3.005 1.245T1.75 10.5v6q0 1.76 1.245 3.005T6 20.75h12q1.76 0 3.005-1.245T22.25 16.5v-6q0-1.76-1.245-3.005T18 6.25M12 9.5q1.657 0 2.828 1.172Q16 11.843 16 13.5q0 4-4 4t-4-4t4-4");
}

</style>
