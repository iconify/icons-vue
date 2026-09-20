<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gul0s-ogc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:matter-outline-rounded" /></template>
<style>
.gul0s-ogc {
  fill: currentColor;
  d: path("M9.435 9.541Q8.23 9.083 7.246 8.277l.915-.556q.6.442 1.435.767q.835.326 1.904.508V3.39l.5-.312l.5.312v5.607q1.03-.183 1.866-.508q.834-.324 1.473-.767l.915.556q-.985.806-2.189 1.264Q13.363 10 12 10t-2.565-.459m.974 9.584l-.946-.513q.031-.148.034-.306T9.5 18q0-.633-.167-1.378t-.483-1.553l-4.844 2.904l-.506-.28v-.58l4.82-2.897q-.655-.749-1.372-1.304q-.717-.556-1.448-.889v-1.08q2.177.77 3.589 2.687T10.5 18q0 .289-.021.568q-.021.28-.07.557m3.181 0q-.048-.277-.069-.557T13.5 18q0-2.454 1.412-4.37q1.411-1.917 3.588-2.688v1.062q-.711.294-1.429.869q-.717.575-1.39 1.343l4.819 2.897v.58l-.506.28l-4.844-2.904q-.315.808-.483 1.553T14.5 18q0 .148.003.306q.003.157.034.305z");
}

</style>
